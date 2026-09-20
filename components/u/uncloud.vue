<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ninrxlcbc.css';
import '../../css/w/wg1goqjvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ninrxlcbc"/><path class="wg1goqjvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uncloud" /></template>
