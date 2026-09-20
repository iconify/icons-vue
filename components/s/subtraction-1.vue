<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-0g1m3_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o-0g1m3_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:subtraction-1" /></template>
