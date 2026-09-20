<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk97sd-8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk97sd-8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wind-line" /></template>
