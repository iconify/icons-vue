<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klg9wvjas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="klg9wvjas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:moon-cloud" /></template>
