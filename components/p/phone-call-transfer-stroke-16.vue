<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw_ciwb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gw_ciwb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-transfer-stroke-16" /></template>
