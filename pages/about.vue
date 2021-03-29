<template>
  <div class="about">
    <h1>About the test</h1>
    <p>
      Tests and evaluation is gathered from Johnson's (2014) 120-item IPIP NEO-PI-R.
    </p>
  </div>
</template>
<script>
import { mdiGithub } from '@mdi/js'
export default {
  name: 'About',
  data () {
    return {
      mdiGithub
    }
  },
  head () {
    return {
      title: this.$t('about.seo.title'),
      meta: [
        { hid: 'title', name: 'title', content: this.$t('about.seo.title') },
        { hid: 'description', name: 'description', content: this.$t('about.seo.description') },
        { hid: 'keywords', name: 'keywords', content: this.$t('seo.keywords') },
        // Open Graph
        { hid: 'og:title', name: 'og:title', content: this.$t('about.seo.title') },
        { hid: 'og:description', name: 'og:description', content: this.$t('about.seo.description') },
        { hid: 'twitter:title', name: 'twitter:title', content: this.$t('about.seo.title') },
        { hid: 'twitter:description', name: 'twitter:description', content: this.$t('about.seo.description') }
      ]
    }
  }
}
</script>
