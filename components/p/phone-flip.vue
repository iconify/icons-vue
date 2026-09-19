<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqiy_7vqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jqiy_7vqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:phone-flip" /></template>
