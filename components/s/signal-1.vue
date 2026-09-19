<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np0tqyb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="np0tqyb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signal-1" /></template>
