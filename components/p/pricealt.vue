<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il9y_2n5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="il9y_2n5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pricealt" /></template>
