<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilw7d2bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ilw7d2bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:solar-panel" /></template>
