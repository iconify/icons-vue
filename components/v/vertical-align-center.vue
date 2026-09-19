<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwi9b4iau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwi9b4iau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:vertical-align-center" /></template>
