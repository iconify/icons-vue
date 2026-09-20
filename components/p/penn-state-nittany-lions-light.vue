<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey75k4bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ey75k4bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:penn-state-nittany-lions-light" /></template>
