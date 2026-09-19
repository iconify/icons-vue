<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk6vu-bip.css';
import '../../css/i/i_urbac4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vk6vu-bip"/><path class="i_urbac4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sunraincloud" /></template>
