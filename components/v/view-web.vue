<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwr34p2qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="mwr34p2qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-web" /></template>
