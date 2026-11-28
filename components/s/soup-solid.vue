<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t93_9wbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t93_9wbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:soup-solid" /></template>
