<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c35ky7bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c35ky7bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sub" /></template>
