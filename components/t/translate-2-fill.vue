<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlltthb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlltthb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:translate-2-fill" /></template>
