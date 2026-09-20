<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1rbdisyq.css';
import '../../css/f/frpnumb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t1rbdisyq"/><path class="frpnumb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:readmeabook-dark" /></template>
