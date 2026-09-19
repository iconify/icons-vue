<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa51_kbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa51_kbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-food" /></template>
