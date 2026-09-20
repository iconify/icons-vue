<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4ql1ybvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p4ql1ybvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-ii" /></template>
