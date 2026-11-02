<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xce7e9krf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xce7e9krf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:question-2-line" /></template>
