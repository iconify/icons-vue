<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_mvaupgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="p_mvaupgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:reader" /></template>
