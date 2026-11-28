<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmmlc-vjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmmlc-vjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wifi-gear" /></template>
