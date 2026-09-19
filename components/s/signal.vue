<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7lr1yx6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="y7lr1yx6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:signal" /></template>
