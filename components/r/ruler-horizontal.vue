<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv6_e7b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cv6_e7b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:ruler-horizontal" /></template>
