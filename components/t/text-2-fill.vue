<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkhnqjboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkhnqjboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-2-fill" /></template>
