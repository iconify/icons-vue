<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxlw5-52r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxlw5-52r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-access-2013-light" /></template>
