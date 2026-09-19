<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm0x5nt_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wm0x5nt_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:table-col-after" /></template>
