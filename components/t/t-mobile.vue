<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv9b7tbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qv9b7tbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:t-mobile" /></template>
