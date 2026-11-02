<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5chi8b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5chi8b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vector-bezier-3-fill" /></template>
