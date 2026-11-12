<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc0j32hhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vc0j32hhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tpdb-light" /></template>
