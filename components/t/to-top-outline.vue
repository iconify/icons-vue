<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf2nnx-8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pf2nnx-8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:to-top-outline" /></template>
