<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdq01i_nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdq01i_nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:selector-vertical-line" /></template>
