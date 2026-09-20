<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m09_hvbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:package-2-rounded" /></template>
<style>
.m09_hvbpp {
  fill: currentColor;
  d: path("M11.5 20.86v-8.573L4 7.95v7.66q0 .434.215.807q.214.373.593.59zm1 0l6.692-3.852q.38-.217.594-.59q.214-.374.214-.808V7.95l-7.5 4.337zm3.667-11.846l3.277-1.88l-6.636-3.82q-.38-.218-.808-.218t-.808.218L8.775 4.708zM12 11.427l3.167-1.835L7.742 5.3L4.57 7.121z");
}

</style>
