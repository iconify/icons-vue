<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq9e1ac5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zq9e1ac5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mic-off-circle" /></template>
