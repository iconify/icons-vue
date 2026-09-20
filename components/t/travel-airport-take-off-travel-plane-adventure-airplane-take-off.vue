<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edgr8yixw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="edgr8yixw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-airport-take-off-travel-plane-adventure-airplane-take-off" /></template>
