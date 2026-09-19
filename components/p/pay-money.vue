<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c625b_u-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c625b_u-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pay-money" /></template>
