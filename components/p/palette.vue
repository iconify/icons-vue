<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxe01ac_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="gxe01ac_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:palette" /></template>
