<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w782_ibba.css';
import '../../css/d/dk77dnbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w782_ibba"/><path class="dk77dnbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-planet" /></template>
