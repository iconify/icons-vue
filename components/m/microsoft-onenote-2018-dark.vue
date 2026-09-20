<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2dr_bsvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s2dr_bsvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onenote-2018-dark" /></template>
