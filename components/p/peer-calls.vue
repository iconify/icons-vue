<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-1c5mb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t-1c5mb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peer-calls" /></template>
