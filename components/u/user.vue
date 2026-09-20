<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4a5arb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q4a5arb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user" /></template>
