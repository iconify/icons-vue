<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2cj1w83c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l2cj1w83c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:purpurmc-dark" /></template>
