<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbowpabjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbowpabjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:pause" /></template>
