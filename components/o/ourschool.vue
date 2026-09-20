<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os1_vdd3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="os1_vdd3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ourschool" /></template>
