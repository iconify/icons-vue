<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkxoxmubt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkxoxmubt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skip-forward-fill" /></template>
