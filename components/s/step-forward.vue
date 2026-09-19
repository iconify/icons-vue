<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqsoy3bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kqsoy3bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:step-forward" /></template>
