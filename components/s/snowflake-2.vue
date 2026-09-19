<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbcc_bcyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zbcc_bcyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:snowflake-2" /></template>
