<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhgq3h-um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhgq3h-um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mosaic-line" /></template>
