<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t48i01_4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="t48i01_4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:shift-fill" /></template>
