<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz0jswbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lz0jswbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-fill-arrow-up-right" /></template>
