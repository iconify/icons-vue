<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cni9eacnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cni9eacnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-amount-up" /></template>
