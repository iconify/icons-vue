<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgrx0uh8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xgrx0uh8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slickdeals-light" /></template>
