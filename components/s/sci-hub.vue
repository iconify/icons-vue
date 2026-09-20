<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpru0-bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="qpru0-bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:sci-hub" /></template>
