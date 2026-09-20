<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ccc6088zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-alert-20-filled" /></template>
<style>
.ccc6088zm {
  fill: currentColor;
  d: path("M9 2a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-4.991 9A2 2 0 0 0 2 13c0 1.691.833 2.966 2.135 3.797C5.417 17.614 7.145 18 9 18a13 13 0 0 0 1.113-.048c-1.116-.287-1.54-1.782-.58-2.596l.966-.82V13c0-.729.195-1.412.535-2zm7.49 2a3 3 0 0 1 6 0v2l1.32 1.119a.5.5 0 0 1-.323.881h-7.993a.5.5 0 0 1-.323-.881L11.5 15zm3 6a1.5 1.5 0 0 1-1.414-1h2.829a1.5 1.5 0 0 1-1.415 1");
}

</style>
