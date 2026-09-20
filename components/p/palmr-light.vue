<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhq-3hb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fhq-3hb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:palmr-light" /></template>
