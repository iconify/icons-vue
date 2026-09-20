<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk8njw3yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hk8njw3yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:network-device-filled" /></template>
