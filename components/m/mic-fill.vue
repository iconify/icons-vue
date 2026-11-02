<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1wv-ub1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1wv-ub1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mic-fill" /></template>
