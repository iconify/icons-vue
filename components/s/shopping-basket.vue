<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itrkz7s2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="itrkz7s2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:shopping-basket" /></template>
