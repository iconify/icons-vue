<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfv5vpb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfv5vpb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netgear-light" /></template>
