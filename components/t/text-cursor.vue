<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk1s0nbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xk1s0nbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-cursor" /></template>
