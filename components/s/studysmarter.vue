<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b7u95cwjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:studysmarter" /></template>
<style>
.b7u95cwjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.578 8.944l17.395 10.055a1.054 1.054 0 0 1 0 1.825L25.578 30.879A3.16 3.16 0 0 0 24 33.614v4.532a1.052 1.052 0 0 0 1.578.91l7.27-4.202a3.16 3.16 0 0 0 1.579-2.735v-4.633a3.16 3.16 0 0 0-1.579-2.736l-7.27-4.202A3.16 3.16 0 0 1 24 17.812V9.854a1.052 1.052 0 0 1 1.578-.91m-3.156 0L5.027 18.999a1.054 1.054 0 0 0 0 1.825l17.395 10.055A3.16 3.16 0 0 1 24 33.614v4.532a1.052 1.052 0 0 1-1.578.91l-7.27-4.202a3.16 3.16 0 0 1-1.579-2.735v-4.633a3.16 3.16 0 0 1 1.579-2.736l7.27-4.202A3.16 3.16 0 0 0 24 17.812V9.854a1.052 1.052 0 0 0-1.578-.91");
}

</style>
