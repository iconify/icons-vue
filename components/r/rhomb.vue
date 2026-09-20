<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh1p2cbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lh1p2cbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rhomb" /></template>
