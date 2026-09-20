<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db7_4kbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db7_4kbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mortarboard-line" /></template>
