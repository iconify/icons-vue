<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl_i03gih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl_i03gih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tree-deciduous-gloss" /></template>
