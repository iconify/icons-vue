<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uetfq1nuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uetfq1nuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:zoom-in-fill" /></template>
