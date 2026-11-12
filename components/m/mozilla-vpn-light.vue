<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb16ibc-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gb16ibc-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mozilla-vpn-light" /></template>
