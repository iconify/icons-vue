<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to1a0gb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="to1a0gb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-info-i" /></template>
