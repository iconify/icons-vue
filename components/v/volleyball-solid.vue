<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9v37qbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9v37qbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:volleyball-solid" /></template>
