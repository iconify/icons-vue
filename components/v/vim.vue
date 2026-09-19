<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kozflou_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kozflou_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:vim" /></template>
