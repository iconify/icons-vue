<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjz_tdl7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kjz_tdl7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nvidia-dark" /></template>
