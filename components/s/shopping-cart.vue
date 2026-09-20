<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyodezbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyodezbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shopping-cart" /></template>
