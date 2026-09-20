<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdp5qyblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdp5qyblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-dark" /></template>
