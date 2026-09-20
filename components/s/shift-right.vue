<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrax_sb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="rrax_sb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:shift-right" /></template>
