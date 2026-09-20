<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc5zfuica.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc5zfuica"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:union-line" /></template>
