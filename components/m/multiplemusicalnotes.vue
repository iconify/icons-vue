<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w973myp8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w973myp8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:multiplemusicalnotes" /></template>
