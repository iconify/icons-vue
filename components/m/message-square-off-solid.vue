<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgku137fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgku137fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-off-solid" /></template>
