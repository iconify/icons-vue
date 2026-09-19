<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh9kkrh5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh9kkrh5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:push" /></template>
