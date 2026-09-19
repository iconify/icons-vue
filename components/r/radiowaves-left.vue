<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6719dbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="l6719dbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:radiowaves-left" /></template>
