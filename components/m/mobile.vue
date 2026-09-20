<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-3e4bb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x-3e4bb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:mobile" /></template>
