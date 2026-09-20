<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy0i9f5du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qy0i9f5du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermark-light" /></template>
