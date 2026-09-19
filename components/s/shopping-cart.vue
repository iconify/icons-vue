<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6iqb18wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u6iqb18wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:shopping-cart" /></template>
