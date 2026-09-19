<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl-bt9n6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cl-bt9n6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:rs-male" /></template>
