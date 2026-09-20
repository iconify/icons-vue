<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p19pt6bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p19pt6bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:picasa" /></template>
