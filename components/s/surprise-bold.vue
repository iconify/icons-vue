<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj2bnvbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yj2bnvbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:surprise-bold" /></template>
