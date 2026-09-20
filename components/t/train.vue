<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6x4_pxoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="k6x4_pxoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:train" /></template>
