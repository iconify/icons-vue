<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcke1qbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcke1qbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:option-fill" /></template>
