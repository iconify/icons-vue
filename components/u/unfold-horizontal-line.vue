<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l220euvzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l220euvzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unfold-horizontal-line" /></template>
