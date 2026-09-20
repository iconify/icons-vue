<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsr4uac1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nsr4uac1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:temu-light" /></template>
