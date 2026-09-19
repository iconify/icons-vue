<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzq_jlble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzq_jlble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:skateboard" /></template>
