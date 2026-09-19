<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnv5u_5dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gnv5u_5dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-line-vertical-square" /></template>
