<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8gl_zb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w8gl_zb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notifuse-light" /></template>
