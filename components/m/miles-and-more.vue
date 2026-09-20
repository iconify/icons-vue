<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocexvzpnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ocexvzpnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:miles-and-more" /></template>
