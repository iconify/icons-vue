<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jul67prvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jul67prvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pi-hole-dark" /></template>
