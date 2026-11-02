<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xye12b3il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xye12b3il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:table-line" /></template>
