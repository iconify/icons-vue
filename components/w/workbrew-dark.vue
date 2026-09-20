<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl7yv0b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yl7yv0b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:workbrew-dark" /></template>
