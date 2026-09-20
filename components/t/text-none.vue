<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_4amlb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f_4amlb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:text-none" /></template>
