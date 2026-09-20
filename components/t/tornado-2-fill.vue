<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzvp85bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzvp85bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tornado-2-fill" /></template>
