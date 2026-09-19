<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d37s1yb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="d37s1yb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:signal" /></template>
