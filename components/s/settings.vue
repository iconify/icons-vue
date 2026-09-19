<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4l0rubrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t4l0rubrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:settings" /></template>
