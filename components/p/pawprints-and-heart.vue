<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0v7beb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s0v7beb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pawprints-and-heart" /></template>
