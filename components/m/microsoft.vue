<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxj4q7bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxj4q7bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:microsoft" /></template>
