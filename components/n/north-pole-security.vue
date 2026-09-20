<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_cut2bia.css';
import '../../css/v/vyoe27bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="o_cut2bia"/><path class="vyoe27bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:north-pole-security" /></template>
