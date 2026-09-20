<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cozkiep2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cozkiep2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:triangle-right" /></template>
