<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve7t91bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ve7t91bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:triton-head" /></template>
