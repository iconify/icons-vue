<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4pi1pb2y.css';
import '../../css/p/pxs3yikcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k4pi1pb2y"/><circle class="pxs3yikcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:search-circle-sharp" /></template>
