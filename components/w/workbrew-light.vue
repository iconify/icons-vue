<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji3_crqts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ji3_crqts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:workbrew-light" /></template>
