<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbme2ub2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mbme2ub2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wheelie-bin-and-apple-core" /></template>
