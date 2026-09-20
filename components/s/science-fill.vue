<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piy1tubod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piy1tubod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:science-fill" /></template>
