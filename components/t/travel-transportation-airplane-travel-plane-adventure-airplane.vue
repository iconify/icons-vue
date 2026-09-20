<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp9o_9agn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rp9o_9agn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-transportation-airplane-travel-plane-adventure-airplane" /></template>
