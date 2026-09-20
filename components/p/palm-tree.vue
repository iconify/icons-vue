<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_zllg1bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a_zllg1bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:palm-tree" /></template>
