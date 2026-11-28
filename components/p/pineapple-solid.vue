<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngyc-38va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngyc-38va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pineapple-solid" /></template>
