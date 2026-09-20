<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wponp31yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wponp31yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:phone" /></template>
