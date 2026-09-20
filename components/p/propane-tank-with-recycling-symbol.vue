<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifsc1nbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ifsc1nbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:propane-tank-with-recycling-symbol" /></template>
