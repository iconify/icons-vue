<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n82dipk4k.css';
import '../../css/z/z55h80buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":75,"height":75};
const content = `<circle class="n82dipk4k"/><path class="z55h80buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:obs" /></template>
