<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6bcjsuzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6bcjsuzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:programming-hold-code-2-bold" /></template>
