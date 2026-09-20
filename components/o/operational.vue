<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-h5b6a8z.css';
import '../../css/m/mqn54kwig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t-h5b6a8z"/><path class="mqn54kwig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:operational" /></template>
