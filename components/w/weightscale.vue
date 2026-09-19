<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4_n57b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1023};
const content = `<path class="p4_n57b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:weightscale" /></template>
