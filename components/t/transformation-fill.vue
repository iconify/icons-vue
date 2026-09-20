<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjt97bc8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xjt97bc8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transformation-fill" /></template>
