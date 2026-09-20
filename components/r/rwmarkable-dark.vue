<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnt-fab5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gnt-fab5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rwmarkable-dark" /></template>
