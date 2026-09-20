<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f94x20bnf.css';
import '../../css/u/u7syfkble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f94x20bnf"/><path class="u7syfkble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:reference-existing-rtl" /></template>
