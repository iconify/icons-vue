<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiz9zxfye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiz9zxfye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:phantom-pair" /></template>
