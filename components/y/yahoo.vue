<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwtv1pcoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":19,"height":24};
const content = `<path class="fwtv1pcoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:yahoo" /></template>
