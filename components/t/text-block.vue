<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qusmpccyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qusmpccyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:text-block" /></template>
