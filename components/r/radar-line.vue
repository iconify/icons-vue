<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7tv91l-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7tv91l-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:radar-line" /></template>
