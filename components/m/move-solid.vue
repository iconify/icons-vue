<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoa16p8ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoa16p8ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:move-solid" /></template>
