<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw3j8x2vl.css';
import '../../css/s/sog-c-_ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rw3j8x2vl"/><path class="sog-c-_ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:romarr" /></template>
