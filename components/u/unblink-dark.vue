<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-qag6b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-qag6b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unblink-dark" /></template>
