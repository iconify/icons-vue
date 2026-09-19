<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xksjlqv_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xksjlqv_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:trim" /></template>
