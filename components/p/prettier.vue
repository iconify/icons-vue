<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmuf8cooy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wmuf8cooy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:prettier" /></template>
