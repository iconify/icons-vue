<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duygepb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="duygepb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:missing-symbol" /></template>
