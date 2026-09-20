<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eau72fb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eau72fb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-nine-eight-eight" /></template>
