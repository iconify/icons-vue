<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr-3m1bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cr-3m1bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:move-sharp" /></template>
