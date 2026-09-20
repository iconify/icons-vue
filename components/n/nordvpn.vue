<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu_idsbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uu_idsbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nordvpn" /></template>
