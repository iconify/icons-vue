<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxpz6x56l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxpz6x56l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:radio" /></template>
