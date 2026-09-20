<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8f6_-atn.css';
import '../../css/b/b_7qycc3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f8f6_-atn"/><path class="b_7qycc3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:volume-up-rtl" /></template>
