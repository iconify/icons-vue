<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n93m6bbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n93m6bbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:multiply" /></template>
