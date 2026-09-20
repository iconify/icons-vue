<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="memgwqb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:omega-32-filled" /></template>
<style>
.memgwqb0n {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14c0 3.435-1.392 6.326-2.889 8.445a21 21 0 0 1-2.653 3.055h4.292a1.25 1.25 0 1 1 0 2.5h-5.84a1.91 1.91 0 0 1-1.912-1.912c0-.611.288-1.162.735-1.52l.25-.205a18.3 18.3 0 0 0 3.086-3.36C26.385 21.14 27.5 18.747 27.5 16c0-6.351-5.149-11.5-11.5-11.5S4.5 9.649 4.5 16c0 2.747 1.115 5.14 2.43 7.003a18.2 18.2 0 0 0 3.337 3.565c.447.358.735.909.735 1.52A1.91 1.91 0 0 1 9.09 30H3.25a1.25 1.25 0 1 1 0-2.5h4.292a21 21 0 0 1-2.653-3.055C3.392 22.326 2 19.435 2 16C2 8.268 8.268 2 16 2");
}

</style>
