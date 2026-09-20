<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-vi64b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n-vi64b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:shuffle" /></template>
