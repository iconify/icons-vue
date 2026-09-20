<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbolm7bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mbolm7bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vue-js-dark" /></template>
