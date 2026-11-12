<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkv94nbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nkv94nbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ovpn-light" /></template>
