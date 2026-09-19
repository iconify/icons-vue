<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe6w1b_gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe6w1b_gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:small-fan" /></template>
