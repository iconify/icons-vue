<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_9bfgfsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_9bfgfsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-15-fill" /></template>
