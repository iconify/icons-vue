<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1mzqkyge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z1mzqkyge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-under-key" /></template>
