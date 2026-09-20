<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po_yurb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="po_yurb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:window-maximize-solid" /></template>
