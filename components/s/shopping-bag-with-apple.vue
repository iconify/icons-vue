<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbk67ub8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tbk67ub8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-apple" /></template>
