<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgqsp2b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="wgqsp2b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:shopping-cart" /></template>
