<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9t5svbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="k9t5svbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:shopping-cart" /></template>
