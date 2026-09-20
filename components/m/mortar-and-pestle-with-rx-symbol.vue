<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqaqnlb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sqaqnlb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mortar-and-pestle-with-rx-symbol" /></template>
