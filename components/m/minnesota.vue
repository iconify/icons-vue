<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-7s7tbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s-7s7tbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:minnesota" /></template>
