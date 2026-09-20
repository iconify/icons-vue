<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7vch6bck.css';
import '../../css/p/p8nic8bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7vch6bck"/><path class="p8nic8bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openvpn" /></template>
