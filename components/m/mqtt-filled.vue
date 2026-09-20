<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy3l7hbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wy3l7hbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:mqtt-filled" /></template>
