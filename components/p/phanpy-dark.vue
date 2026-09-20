<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h573k5_3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h573k5_3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phanpy-dark" /></template>
