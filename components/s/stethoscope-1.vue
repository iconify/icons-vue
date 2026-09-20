<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu-vt6bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="gu-vt6bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:stethoscope-1" /></template>
