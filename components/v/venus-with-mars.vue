<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br_g0_8yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="br_g0_8yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:venus-with-mars" /></template>
