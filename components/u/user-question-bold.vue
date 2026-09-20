<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylh9a2_wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylh9a2_wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:user-question-bold" /></template>
