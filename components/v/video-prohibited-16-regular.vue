<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c64f99s1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-prohibited-16-regular" /></template>
<style>
.c64f99s1g {
  fill: currentColor;
  d: path("M4.5 6a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-2.096 7.303a3.5 3.5 0 0 0 4.898-4.898zM9.5 3A2.5 2.5 0 0 1 12 5.5v.129l2.035-1.405a1.25 1.25 0 0 1 1.961 1.028v5.498a1.25 1.25 0 0 1-1.96 1.028L12 10.373v.127A2.5 2.5 0 0 1 9.5 13h-.102q.251-.49.402-1.03A1.5 1.5 0 0 0 11 10.5v-5A1.5 1.5 0 0 0 9.5 4h-5a1.5 1.5 0 0 0-1.47 1.2q-.54.15-1.03.4v-.1A2.5 2.5 0 0 1 4.5 3zm-5 4a3.5 3.5 0 0 0-2.803 5.596l4.899-4.899A3.5 3.5 0 0 0 4.5 7m10.496-1.748a.25.25 0 0 0-.393-.205L12 6.844v2.313l2.604 1.798a.25.25 0 0 0 .392-.205z");
}

</style>
