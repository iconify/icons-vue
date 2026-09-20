<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onssh9hzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="onssh9hzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tigera-light" /></template>
