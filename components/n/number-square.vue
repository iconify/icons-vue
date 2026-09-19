<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb3519b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xb3519b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:number-square" /></template>
