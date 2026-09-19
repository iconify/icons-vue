<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwx98lbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="jwx98lbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:xbox" /></template>
