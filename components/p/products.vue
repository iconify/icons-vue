<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3kqflice.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l3kqflice"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:products" /></template>
