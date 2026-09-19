<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdmtibc3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rdmtibc3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-split-1x2-fill" /></template>
