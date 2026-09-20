<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3n7f0bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3n7f0bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:waves-horizontal" /></template>
