<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9d51b_-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v9d51b_-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:snowflake-1" /></template>
