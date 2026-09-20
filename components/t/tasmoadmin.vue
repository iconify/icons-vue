<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp_egdbju.css';
import '../../css/n/nxo71mbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="xp_egdbju"/><path class="nxo71mbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tasmoadmin" /></template>
