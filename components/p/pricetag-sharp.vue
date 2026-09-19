<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_mr8vw2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j_mr8vw2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pricetag-sharp" /></template>
