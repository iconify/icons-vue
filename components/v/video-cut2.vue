<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uept9jgfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uept9jgfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-cut2" /></template>
