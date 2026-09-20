<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol_yukdmc.css';
import '../../css/t/tk2f-4kpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol_yukdmc"/><path class="tk2f-4kpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pizza-2" /></template>
