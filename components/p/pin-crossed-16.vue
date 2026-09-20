<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ongl97bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ongl97bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pin-crossed-16" /></template>
