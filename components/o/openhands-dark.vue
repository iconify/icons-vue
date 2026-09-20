<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgv7ffjnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mgv7ffjnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openhands-dark" /></template>
