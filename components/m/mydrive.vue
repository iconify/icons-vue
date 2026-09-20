<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl7vwl9vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dl7vwl9vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mydrive" /></template>
