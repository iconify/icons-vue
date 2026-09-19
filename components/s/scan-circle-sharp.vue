<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f31idh9jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f31idh9jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:scan-circle-sharp" /></template>
