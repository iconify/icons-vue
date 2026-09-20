<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj-43bcmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj-43bcmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vector-bezier-line" /></template>
