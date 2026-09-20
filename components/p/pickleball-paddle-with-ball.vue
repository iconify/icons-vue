<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9x3on9_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f9x3on9_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickleball-paddle-with-ball" /></template>
