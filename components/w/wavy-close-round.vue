<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtc5v_8lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtc5v_8lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-close-round" /></template>
