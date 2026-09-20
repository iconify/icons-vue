<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_qercbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w_qercbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-top-right" /></template>
