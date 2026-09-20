<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg-ft1bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hg-ft1bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:square-cap-remix" /></template>
