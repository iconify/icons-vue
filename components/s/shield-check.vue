<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks26x0d-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":480};
const content = `<path class="ks26x0d-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:shield-check" /></template>
