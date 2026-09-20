<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pbcj5k96a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-32-regular" /></template>
<style>
.pbcj5k96a {
  fill: currentColor;
  d: path("M12.072 4.306c1.717-3.074 6.14-3.074 7.857 0l9.494 16.998c1.675 3-.493 6.694-3.928 6.694H6.506c-3.435 0-5.603-3.695-3.928-6.694zm6.111.975c-.954-1.707-3.411-1.707-4.365 0L4.324 22.28c-.93 1.666.274 3.719 2.182 3.719h18.989c1.908 0 3.113-2.053 2.182-3.719zM16 19.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3M16 9a1 1 0 0 1 1 1v6.5a1 1 0 0 1-2 0V10a1 1 0 0 1 1-1");
}

</style>
