<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsl32d72m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsl32d72m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skirt-line" /></template>
