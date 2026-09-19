<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3-85c9ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3-85c9ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:square-sharp" /></template>
