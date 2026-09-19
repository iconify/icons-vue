<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pblqpub0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="pblqpub0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:yahoo" /></template>
