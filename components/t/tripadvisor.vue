<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okfx_dzuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="okfx_dzuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:tripadvisor" /></template>
