<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym6-ufb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym6-ufb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pill" /></template>
