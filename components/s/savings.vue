<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adq8x7bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adq8x7bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:savings" /></template>
