<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqspvlzll.css';
import '../../css/s/sppq3wb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gqspvlzll"/><path class="sppq3wb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meshtastic" /></template>
