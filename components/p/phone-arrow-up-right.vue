<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xspkb44qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xspkb44qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-arrow-up-right" /></template>
