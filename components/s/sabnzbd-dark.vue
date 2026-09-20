<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc182sbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wc182sbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sabnzbd-dark" /></template>
