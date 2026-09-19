<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djer2lbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="djer2lbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-on-circle" /></template>
