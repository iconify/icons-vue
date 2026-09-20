<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s340dhbaz.css';
import '../../css/f/fr5_r8b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s340dhbaz"/><path class="fr5_r8b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-vpn-dark" /></template>
