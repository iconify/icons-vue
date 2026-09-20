<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skybz2z3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="skybz2z3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:x-axis-settings" /></template>
