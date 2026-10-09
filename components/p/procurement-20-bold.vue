<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix679zbux.css';
import '../../css/l/lh-bp5b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ix679zbux"/><path class="lh-bp5b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:procurement-20-bold" /></template>
