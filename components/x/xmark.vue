<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2b_8yxjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w2b_8yxjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:xmark" /></template>
