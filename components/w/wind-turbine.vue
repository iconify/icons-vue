<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufs6mebkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ufs6mebkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wind-turbine" /></template>
