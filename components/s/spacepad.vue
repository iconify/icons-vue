<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psk9w-asf.css';
import '../../css/m/mqh2rrbti.css';
import '../../css/s/sb8cqvbau.css';
import '../../css/i/iypdzxlxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="psk9w-asf"/><path class="mqh2rrbti"/><path class="sb8cqvbau"/><circle class="iypdzxlxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spacepad" /></template>
