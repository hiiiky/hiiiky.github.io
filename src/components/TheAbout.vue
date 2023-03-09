<script setup>
import AboutItem from '@/components/AboutItem.vue'
import DocumentationIcon from '@/components/icons/IconDocumentation.vue'
import SupportIcon from '@/components/icons/IconSupport.vue'
</script>

<template>
  <AboutItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Born and raised</template>
    Born and raised in Dublin Ireland
  </AboutItem>

  <AboutItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Education</template>
    Studied Computer Science in Dublin Insitute of Technology (now TUD)
  </AboutItem>

  <AboutItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Work</template>
    Work @ <a href="https://www.docosoft.com/" target="_blank">DOCOsoft</a> as a full stack
    developer
  </AboutItem>

  <AboutItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Interests & Hobbies</template>
    Football, Formula 1, DIY
  </AboutItem>
</template>
