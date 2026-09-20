<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijg_ljbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijg_ljbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:star-half-fill" /></template>
