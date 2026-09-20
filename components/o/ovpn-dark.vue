<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whew0bbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="whew0bbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ovpn-dark" /></template>
