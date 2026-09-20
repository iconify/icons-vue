<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul2plrb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ul2plrb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:upload" /></template>
