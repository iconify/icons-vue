<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4aovbctb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:top" /></template>
<style>
.f4aovbctb {
  fill: var(--svg-color--f8cf03, #f8cf03);
  d: path("M5.004 3.986a2.003 2.003 0 1 0 0 4.007h1.001a2.004 2.004 0 0 0 0-4.007zm7.092 0h6.932a2.003 2.003 0 0 1 0 4.007h-4.315a.694.694 0 0 0-.694.695v9.317a2.01 2.01 0 0 1-4.018 0c.004-3.175.011-9.269.011-12.055c0-.769.403-1.963 2.083-1.963");
}

</style>
