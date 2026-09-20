<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt-w9bcpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dt-w9bcpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:notifications" /></template>
