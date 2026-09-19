<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7_840-vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i7_840-vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-bubble" /></template>
