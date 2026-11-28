<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4jxw57qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4jxw57qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-plus-solid" /></template>
