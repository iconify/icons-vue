<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v51h_ttym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v51h_ttym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skateboard-line" /></template>
