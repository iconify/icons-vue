<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksl-n8z_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ksl-n8z_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:search-dollar" /></template>
