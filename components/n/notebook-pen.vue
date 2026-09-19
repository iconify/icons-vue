<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-0nzsqfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-0nzsqfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:notebook-pen" /></template>
