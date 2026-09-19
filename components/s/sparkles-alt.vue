<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl7ywbc8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl7ywbc8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sparkles-alt" /></template>
