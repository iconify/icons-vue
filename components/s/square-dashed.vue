<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnbt39boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnbt39boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-dashed" /></template>
