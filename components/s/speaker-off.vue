<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwtb72bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vwtb72bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:speaker-off" /></template>
