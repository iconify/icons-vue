<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mew4heblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mew4heblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-left-fill" /></template>
