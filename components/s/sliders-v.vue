<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g64y4bcfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g64y4bcfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sliders-v" /></template>
