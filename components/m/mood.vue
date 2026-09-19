<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwrsxql2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="lwrsxql2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:mood" /></template>
