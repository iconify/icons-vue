<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfi-3h6ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfi-3h6ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-bag-2-line" /></template>
