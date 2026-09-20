<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we4cfybou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we4cfybou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:moon-clear-fill" /></template>
