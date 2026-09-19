<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ive6bserv.css';
import '../../css/u/ur8mbpnqr.css';
import '../../css/n/nxheq_lap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="ive6bserv"/><circle class="ur8mbpnqr"/><path class="nxheq_lap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:shopping-cart" /></template>
