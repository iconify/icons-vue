<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpmg4f9qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mpmg4f9qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:user-plus" /></template>
