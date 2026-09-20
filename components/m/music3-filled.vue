<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grfzoublw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grfzoublw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music3-filled" /></template>
