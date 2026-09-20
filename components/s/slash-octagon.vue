<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq7b6qb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq7b6qb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:slash-octagon" /></template>
