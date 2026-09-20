<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5sa_0a6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5sa_0a6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:route-fill" /></template>
