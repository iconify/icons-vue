<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mc66fobwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:surface-hub-20-filled" /></template>
<style>
.mc66fobwb {
  fill: currentColor;
  d: path("M5.259 2a.5.5 0 0 0-.498.453l-.759 8A.5.5 0 0 0 4.5 11h2.423l-.918 6.43a.5.5 0 0 0 .99.14L7.362 15h2.99l-.347 2.43a.5.5 0 0 0 .99.14l.367-2.57h2.276l.367 2.57a.5.5 0 0 0 .99-.14L14.077 11h.664a.5.5 0 0 0 .498-.453l.759-8A.5.5 0 0 0 15.5 2zm8.236 12h-1.99l.429-3h1.132zm-3 0h-2.99l.429-3h2.99z");
}

</style>
