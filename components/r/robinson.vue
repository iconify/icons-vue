<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loedw3efo.css';
import '../../css/f/fas83m7xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="loedw3efo"/><path class="fas83m7xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:robinson" /></template>
