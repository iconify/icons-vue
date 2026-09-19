<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-3m1rb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="i-3m1rb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:play-circle" /></template>
