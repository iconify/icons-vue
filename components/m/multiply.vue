<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skl2_xb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="skl2_xb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:multiply" /></template>
