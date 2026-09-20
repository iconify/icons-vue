<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g46yxebiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g46yxebiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user-x" /></template>
