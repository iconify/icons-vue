<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/outuwdbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="outuwdbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:radar" /></template>
