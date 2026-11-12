<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rllixy2pz.css';
import '../../css/d/d7qghsrap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rllixy2pz"/><path class="d7qghsrap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:webhook-tester-dark" /></template>
