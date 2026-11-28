<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdj9x2b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdj9x2b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:outlet-solid" /></template>
