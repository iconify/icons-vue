<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfjqcobwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfjqcobwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:simplenote" /></template>
