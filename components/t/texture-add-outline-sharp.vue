<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4-iwpkzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:texture-add-outline-sharp" /></template>
<style>
.a4-iwpkzl {
  fill: currentColor;
  d: path("M4.708 20H4v-.708L19.292 4h.714v.708zM4 13.527v-1.415L12.111 4h1.416zm0-7.18V4h2.346zm16 4.126v1.416l-.167.167q-.25-.115-.515-.205t-.557-.14zM10.473 20l1.7-1.7q.05.292.14.557t.204.514L11.89 20zM17 17.538h-3v-1h3v-3h1v3h3v1h-3v3h-1z");
}

</style>
