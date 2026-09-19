<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj_gb8-5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uj_gb8-5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:table-cells" /></template>
