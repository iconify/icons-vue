<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6dfp0bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6dfp0bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:perspective-off" /></template>
