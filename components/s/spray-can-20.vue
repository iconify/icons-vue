<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb0u2kbzg.css';
import '../../css/t/t-m8w0bde.css';
import '../../css/l/l1ws3p1do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zb0u2kbzg"/><path class="t-m8w0bde"/><path class="l1ws3p1do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spray-can-20" /></template>
