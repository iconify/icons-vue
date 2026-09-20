<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wit17ea4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wit17ea4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:shopping-cart" /></template>
