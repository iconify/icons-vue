<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqs8f3gob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eqs8f3gob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:usb-memory-stick" /></template>
