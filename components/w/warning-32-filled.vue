<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="egazvc0cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-32-filled" /></template>
<style>
.egazvc0cl {
  fill: currentColor;
  d: path("M12.072 4.306c1.717-3.074 6.14-3.073 7.857 0l9.494 16.998c1.676 3-.493 6.694-3.928 6.694H6.505c-3.435 0-5.604-3.695-3.928-6.694zm3.93 15.193a1.5 1.5 0 1 0 .001 3.002a1.5 1.5 0 0 0-.002-3.002m0-10.5a1 1 0 0 0-1 1v6.5a1 1 0 0 0 2 0v-6.5c-.001-.552-.449-1-1-1");
}

</style>
