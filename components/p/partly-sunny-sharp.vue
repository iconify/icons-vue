<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw5ybfjdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lw5ybfjdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:partly-sunny-sharp" /></template>
