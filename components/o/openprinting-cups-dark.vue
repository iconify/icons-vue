<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk6wy_3eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tk6wy_3eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openprinting-cups-dark" /></template>
