<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njtq08kwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="njtq08kwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ruler" /></template>
