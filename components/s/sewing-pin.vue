<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj2re3b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dj2re3b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:sewing-pin" /></template>
