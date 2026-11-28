<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzunbmz8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzunbmz8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-function-solid" /></template>
