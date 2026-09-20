<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg1z4-d7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg1z4-d7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shopping-basket-remove" /></template>
