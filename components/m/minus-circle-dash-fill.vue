<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjw_debfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjw_debfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:minus-circle-dash-fill" /></template>
