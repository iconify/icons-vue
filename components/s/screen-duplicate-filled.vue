<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spg-nfber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="spg-nfber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:screen-duplicate-filled" /></template>
