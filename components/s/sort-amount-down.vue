<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shm6wfbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="shm6wfbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-amount-down" /></template>
