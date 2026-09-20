<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mntvm5-5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mntvm5-5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tavily" /></template>
