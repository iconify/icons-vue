<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjujxpbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjujxpbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sailboat-fill" /></template>
