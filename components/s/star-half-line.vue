<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io3z3bc1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io3z3bc1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:star-half-line" /></template>
