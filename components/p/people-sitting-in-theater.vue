<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-w2wcd_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p-w2wcd_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-sitting-in-theater" /></template>
