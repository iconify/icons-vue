<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":254};
const content = `<path class="jq0pzm_mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:scale-ai-icon" /></template>
<style>
.jq0pzm_mc {
  d: path("M14.724 0h226.58C249.421 0 256 6.517 256 14.562v224.505c0 12.965-15.823 19.468-25.084 10.293L4.337 24.854C-4.923 15.679 1.626 0 14.724 0m90.94 142.59c3.553 0 6.42 2.857 6.42 6.363v98.01c0 5.668-6.905 8.496-10.943 4.495l-98.915-98.01c-4.037-4-1.184-10.843 4.537-10.843h98.9z");
}

</style>
