<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc0v658tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":432};
const content = `<path class="gc0v658tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:male-female" /></template>
