<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tznw7je4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tznw7je4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:text-align-center" /></template>
