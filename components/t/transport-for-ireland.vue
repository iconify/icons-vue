<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysyqdbbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysyqdbbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:transport-for-ireland" /></template>
