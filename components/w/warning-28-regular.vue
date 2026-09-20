<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="x9b-u5b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-28-regular" /></template>
<style>
.x9b-u5b3c {
  fill: currentColor;
  d: path("M10.738 4.896c1.438-2.528 5.083-2.528 6.52 0l8.243 14.502c1.42 2.5-.384 5.603-3.26 5.603H5.756c-2.876 0-4.681-3.103-3.26-5.603zm5.216.742c-.863-1.517-3.05-1.517-3.912 0L3.8 20.14c-.853 1.5.23 3.361 1.956 3.361H22.24c1.725 0 2.808-1.861 1.956-3.361zM14 18a1 1 0 1 1 0 2a1 1 0 0 1 0-2m0-9a.75.75 0 0 1 .75.75v6a.75.75 0 0 1-1.5 0v-6A.75.75 0 0 1 14 9");
}

</style>
