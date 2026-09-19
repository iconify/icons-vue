<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uauxjs-rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uauxjs-rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:wand-rays" /></template>
