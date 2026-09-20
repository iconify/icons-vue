<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t10d3dbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t10d3dbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:marriott" /></template>
