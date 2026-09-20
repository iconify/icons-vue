<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kliljjg0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kliljjg0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mens-restroom-symbol" /></template>
