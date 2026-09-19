<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixf3ftt8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixf3ftt8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:sad" /></template>
