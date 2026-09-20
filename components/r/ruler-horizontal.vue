<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl2r66bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pl2r66bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ruler-horizontal" /></template>
