<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra0v5m8_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ra0v5m8_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-with-stethoscope" /></template>
