<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwcfi3o_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwcfi3o_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trophy-line" /></template>
