<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkfdg3zno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wkfdg3zno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scuttle-dark" /></template>
