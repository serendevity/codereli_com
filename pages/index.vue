<template>
  <main class="flex-1">
    <SectionsHeroSection />
    <SectionsSocialProuf />
    <SectionsLogoCloud />
    <SectionsServices />
    <SectionsAboutContent />
    <SectionsCta />
  </main>
</template>

<script lang="ts" setup>
useHead({
  title: 'Codereli: Elevating Ideas through Innovative Software Solutions',
  meta: [
    {
      name: 'description',
      content: 'Innovative Software Development Company - Crafting Solutions for the Digital World',
    },
    {
      name: 'author',
      content: 'Codereli'
    },
    {
      name: 'keywords',
      content: 'custom software development, web application development, mobile app development, software solutions, software engineering, agile development, scalable solutions, technology consulting, code optimization, UX/UI design, cloud computing, software architecture, digital transformation, IT services, software maintenance, quality assurance, innovative coding, tech solutions, responsive web design, cross-platform development'
    }
  ],
  link: [
    {
      href: "https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500;600;700&display=swap",
      rel: "stylesheet"
    }
  ],
})
</script>
