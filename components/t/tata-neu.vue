<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lrcni7b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tata-neu" /></template>
<style>
.lrcni7b6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.383 31.256l6.368-16.108c1.49-4.344 5.222-4.815 6.79-.474a94 94 0 0 0 2.977 9.078l5.39-12.185c3.937-6.82 14.723-1.363 10.571 6.103L26.465 39.273c-1 1.97-7.595 5.948-9.366-1.317c-.954-5.034-2.36-13.859-2.36-13.859L9.63 32.712c-.883 1.53-4.023 1.422-3.248-1.457zm16.135-7.504l-5.631 12.68m-2.149-12.335l-1.696-9.416");
}

</style>
