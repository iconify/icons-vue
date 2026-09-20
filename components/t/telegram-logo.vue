<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8ix5nblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d8ix5nblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:telegram-logo" /></template>
