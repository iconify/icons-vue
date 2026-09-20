<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgcjudb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hgcjudb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:moustache" /></template>
