<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiwhcobkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qiwhcobkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:solar-energy-alt" /></template>
