<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usl5inb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="usl5inb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voron-dark" /></template>
