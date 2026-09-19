<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi5he_bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="mi5he_bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:pocket" /></template>
