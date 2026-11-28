<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6wr2vbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6wr2vbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:square-1" /></template>
