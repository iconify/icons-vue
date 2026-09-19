<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs_sp7bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="hs_sp7bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squareone" /></template>
