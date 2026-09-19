<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_w699bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_w699bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-skip-back-sharp" /></template>
