<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh2c8vt1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":24};
const content = `<path class="bh2c8vt1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:rocket" /></template>
