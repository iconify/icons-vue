<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oab_xla-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oab_xla-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:sos-phone" /></template>
