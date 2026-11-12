<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozy00iotv.css';
import '../../css/x/xlao23b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ozy00iotv"/><path class="xlao23b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nasa-dark" /></template>
