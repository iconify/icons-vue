<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d94gv9lat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d94gv9lat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-and-tag" /></template>
