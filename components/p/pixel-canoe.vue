<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkese0awh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lkese0awh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-canoe" /></template>
