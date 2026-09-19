<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfue8cbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hfue8cbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:wrench" /></template>
