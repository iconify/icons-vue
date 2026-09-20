<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed3nujbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ed3nujbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:triangle-down" /></template>
