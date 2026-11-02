<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce3a2vb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce3a2vb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:quarter-circle-dash-fill" /></template>
