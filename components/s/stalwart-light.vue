<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlsql2bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dlsql2bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stalwart-light" /></template>
