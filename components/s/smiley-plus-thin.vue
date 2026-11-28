<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4vabbcny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i4vabbcny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:smiley-plus-thin" /></template>
