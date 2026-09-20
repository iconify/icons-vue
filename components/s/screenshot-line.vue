<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae_qjzbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae_qjzbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:screenshot-line" /></template>
