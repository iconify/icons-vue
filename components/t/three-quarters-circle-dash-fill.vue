<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_ybpbcve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_ybpbcve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:three-quarters-circle-dash-fill" /></template>
