<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvf2eacwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvf2eacwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tent" /></template>
