<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpcc2ybdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpcc2ybdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:toggle-on-filled" /></template>
