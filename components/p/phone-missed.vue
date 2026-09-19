<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omwx7-b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="omwx7-b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:phone-missed" /></template>
