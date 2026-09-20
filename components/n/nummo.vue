<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmx-y7bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qmx-y7bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nummo" /></template>
