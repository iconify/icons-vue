<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6jz-quxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6jz-quxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-brush-outline" /></template>
