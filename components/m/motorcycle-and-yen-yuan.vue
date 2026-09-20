<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw2vlobaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cw2vlobaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-and-yen-yuan" /></template>
