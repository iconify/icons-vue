<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnhmo3bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnhmo3bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:warning-circle-solid" /></template>
