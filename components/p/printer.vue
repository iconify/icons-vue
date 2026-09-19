<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc1by1b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oc1by1b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:printer" /></template>
