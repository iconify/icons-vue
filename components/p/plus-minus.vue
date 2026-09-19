<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6a0yfbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="d6a0yfbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plus-minus" /></template>
