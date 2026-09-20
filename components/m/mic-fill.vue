<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzekj1ekw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzekj1ekw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mic-fill" /></template>
