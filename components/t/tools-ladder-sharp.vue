<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-51stbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tools-ladder-sharp" /></template>
<style>
.r-51stbfo {
  fill: currentColor;
  d: path("m5.873 20.5l4.73-17h.943l-.83 3h5.605l.844-3h.962l-4.73 17h-.943l.83-3H7.68l-.845 3zm3.468-9h5.6l1.113-4h-5.62zm-1.395 5h5.62l1.093-4h-5.6z");
}

</style>
