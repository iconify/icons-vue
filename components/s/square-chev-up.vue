<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2dnpkjjq.css';
import '../../css/z/z456xsbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2dnpkjjq"/><path class="z456xsbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:square-chev-up" /></template>
