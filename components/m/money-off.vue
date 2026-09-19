<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-4if6c6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="n-4if6c6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:money-off" /></template>
