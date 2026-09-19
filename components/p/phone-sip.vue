<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy3b7ss8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="hy3b7ss8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:phone-sip" /></template>
