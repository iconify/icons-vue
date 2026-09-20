<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo5algb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo5algb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:play" /></template>
