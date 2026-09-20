<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufjnn8nee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ufjnn8nee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:text-align-justify" /></template>
