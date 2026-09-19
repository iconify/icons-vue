<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6gf_ppof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q6gf_ppof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-arrow-right" /></template>
