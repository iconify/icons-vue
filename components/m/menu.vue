<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxxmedclj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxxmedclj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:menu" /></template>
