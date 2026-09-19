<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4t6h1u3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g4t6h1u3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:removefriend" /></template>
