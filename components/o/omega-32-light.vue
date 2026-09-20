<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hq3eaccrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:omega-32-light" /></template>
<style>
.hq3eaccrz {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14c0 3.463-1.643 6.4-3.429 8.574a23 23 0 0 1-4.496 4.143a.17.17 0 0 0-.075.139c0 .08.065.144.145.144H29.5a.5.5 0 0 1 0 1h-7.355A1.145 1.145 0 0 1 21 28.855c0-.39.194-.745.508-.961c.7-.483 2.585-1.878 4.29-3.954C27.509 21.86 29 19.14 29 16c0-7.18-5.82-13-13-13S3 8.82 3 16c0 3.141 1.492 5.86 3.201 7.94a22 22 0 0 0 4.291 3.954c.314.216.508.572.508.962C11 29.487 10.488 30 9.855 30H2.5a.5.5 0 0 1 0-1h7.355c.08 0 .145-.065.145-.145a.17.17 0 0 0-.075-.138a23 23 0 0 1-4.496-4.143C3.643 22.401 2 19.464 2 16C2 8.268 8.268 2 16 2");
}

</style>
