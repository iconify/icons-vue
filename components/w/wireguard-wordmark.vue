<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpg-nubov.css';
import '../../css/f/fhcl44oal.css';
import '../../css/q/qijlvrbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vpg-nubov"/><path class="fhcl44oal"/><path class="qijlvrbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:wireguard-wordmark" /></template>
