<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw1v71bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dw1v71bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nocodb-dark" /></template>
