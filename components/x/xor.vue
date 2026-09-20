<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of4gs732s.css';
import '../../css/c/caxag_z2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of4gs732s"/><path class="caxag_z2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xor" /></template>
