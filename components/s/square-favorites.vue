<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeq2uhbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zeq2uhbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-favorites" /></template>
