<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qus4oocsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qus4oocsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-wrap-fill-round" /></template>
