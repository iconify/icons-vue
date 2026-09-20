<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygmh30bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygmh30bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zigbee" /></template>
