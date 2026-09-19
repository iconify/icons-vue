<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u03tmmbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u03tmmbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:slash-circle-fill" /></template>
