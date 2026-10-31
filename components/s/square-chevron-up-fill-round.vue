<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwl12gbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwl12gbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-up-fill-round" /></template>
