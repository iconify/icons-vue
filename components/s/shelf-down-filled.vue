<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5jkcbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xn5jkcbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:shelf-down-filled" /></template>
