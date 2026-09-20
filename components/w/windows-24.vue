<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af-zpmbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af-zpmbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:windows-24" /></template>
