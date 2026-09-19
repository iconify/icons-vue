<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7sy1g2se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o7sy1g2se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sort-amount-up" /></template>
