<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/salrc2btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="salrc2btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pve-ups-light" /></template>
