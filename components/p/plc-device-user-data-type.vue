<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udyu9pxgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="udyu9pxgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plc-device-user-data-type" /></template>
