<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7gn9tbal.css';
import '../../css/g/g2_udexnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7gn9tbal"/><path class="g2_udexnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-ribbon-bold" /></template>
