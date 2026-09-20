<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foe_-tb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="foe_-tb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sipeed-light" /></template>
