<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyic26gyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eyic26gyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:symbol" /></template>
