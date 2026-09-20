<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m16-f66mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m16-f66mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:scale-unbalanced" /></template>
