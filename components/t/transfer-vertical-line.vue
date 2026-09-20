<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze1ar8xrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze1ar8xrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-vertical-line" /></template>
