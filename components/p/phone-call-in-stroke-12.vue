<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_u2c4bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="w_u2c4bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-in-stroke-12" /></template>
