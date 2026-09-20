<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0q_-7bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0q_-7bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-5-line" /></template>
