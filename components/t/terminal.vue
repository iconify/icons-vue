<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi2wt22zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi2wt22zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:terminal" /></template>
