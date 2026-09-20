<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjfq8ra2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kjfq8ra2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:z-wave-dark" /></template>
