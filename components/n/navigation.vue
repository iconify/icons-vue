<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcosuhb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":408};
const content = `<path class="dcosuhb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:navigation" /></template>
