<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fej4g_csw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fej4g_csw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:socket-io-light" /></template>
