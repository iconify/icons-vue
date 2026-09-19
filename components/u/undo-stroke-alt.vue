<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twyu62blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twyu62blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:undo-stroke-alt" /></template>
