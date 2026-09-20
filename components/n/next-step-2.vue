<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ookuxubeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="ookuxubeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:next-step-2" /></template>
