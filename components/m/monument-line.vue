<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsd79yplg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsd79yplg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:monument-line" /></template>
