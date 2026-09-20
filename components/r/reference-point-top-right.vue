<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kljlrcurh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kljlrcurh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:reference-point-top-right" /></template>
