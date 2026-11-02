<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c52ptkc9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c52ptkc9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-align-end-fill" /></template>
