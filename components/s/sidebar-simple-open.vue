<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gda9zkbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gda9zkbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-open" /></template>
