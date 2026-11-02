<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_72bhbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_72bhbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:notebook-2-line" /></template>
