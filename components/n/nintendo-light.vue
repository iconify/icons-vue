<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9xarfbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9xarfbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nintendo-light" /></template>
