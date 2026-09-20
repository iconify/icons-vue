<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhyokkxsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zhyokkxsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:pencil" /></template>
