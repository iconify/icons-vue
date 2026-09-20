<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-bmdtxyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x-bmdtxyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-open-book" /></template>
