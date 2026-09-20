<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4wm8jbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-star-48-filled" /></template>
<style>
.r4wm8jbis {
  fill: currentColor;
  d: path("M16 22a8 8 0 1 0 0-16a8 8 0 0 0 0 16m18 0a6 6 0 1 0 0-12a6 6 0 0 0 0 12M6.75 25A3.75 3.75 0 0 0 3 28.75V30s0 9 13 9c2.61 0 4.695-.363 6.362-.942A13 13 0 0 1 22 35a12.97 12.97 0 0 1 4.459-9.8c-.38-.13-.786-.2-1.209-.2zM46 35c0 6.075-4.925 11-11 11s-11-4.925-11-11s4.925-11 11-11s11 4.925 11 11m-9.81-6.599a1.236 1.236 0 0 0-2.38 0l-1.194 3.83h-3.862c-1.213 0-1.716 1.617-.736 2.36l3.125 2.366l-1.194 3.83c-.374 1.201.945 2.2 1.926 1.458L35 39.878l3.125 2.367c.98.743 2.3-.257 1.925-1.458l-1.193-3.83l3.125-2.367c.98-.742.477-2.36-.736-2.36h-3.862z");
}

</style>
