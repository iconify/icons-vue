<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7d4biy9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7d4biy9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-basket-round" /></template>
