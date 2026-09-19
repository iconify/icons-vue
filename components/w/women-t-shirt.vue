<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql8bb5b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql8bb5b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:women-t-shirt" /></template>
