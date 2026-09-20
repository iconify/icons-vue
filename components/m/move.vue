<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-8_6ui7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t-8_6ui7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:move" /></template>
