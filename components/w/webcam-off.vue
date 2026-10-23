<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljlzq2dvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljlzq2dvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:webcam-off" /></template>
