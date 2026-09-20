<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w12sadcfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w12sadcfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:multiply" /></template>
