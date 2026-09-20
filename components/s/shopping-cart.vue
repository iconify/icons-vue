<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppdy_ccdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ppdy_ccdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:shopping-cart" /></template>
