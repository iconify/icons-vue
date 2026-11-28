<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qunw-5bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qunw-5bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pipe-solid" /></template>
