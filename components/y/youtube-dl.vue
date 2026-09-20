<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h683xnbcm.css';
import '../../css/i/ima57ac7n.css';
import '../../css/m/mdfbtzb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h683xnbcm"/><circle class="ima57ac7n"/><path class="mdfbtzb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:youtube-dl" /></template>
