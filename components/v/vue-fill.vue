<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh7u_yvuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh7u_yvuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vue-fill" /></template>
