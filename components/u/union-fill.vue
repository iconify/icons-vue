<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcp55eb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dcp55eb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:union-fill" /></template>
