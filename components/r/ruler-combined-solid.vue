<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmhpr2b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vmhpr2b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ruler-combined-solid" /></template>
