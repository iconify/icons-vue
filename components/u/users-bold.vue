<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upi0unbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="upi0unbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:users-bold" /></template>
