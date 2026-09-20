<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf8p8nt7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sf8p8nt7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:view-vertical" /></template>
