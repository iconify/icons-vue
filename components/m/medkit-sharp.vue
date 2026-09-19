<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u98qkxxfj.css';
import '../../css/y/yy95vwqvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u98qkxxfj"/><path class="yy95vwqvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:medkit-sharp" /></template>
