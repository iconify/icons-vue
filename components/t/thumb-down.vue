<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al7f0nbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="al7f0nbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:thumb-down" /></template>
