<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku0ntlbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ku0ntlbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-with-raised-hood-under-wrench" /></template>
