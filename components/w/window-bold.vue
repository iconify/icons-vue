<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_4mexbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="t_4mexbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:window-bold" /></template>
