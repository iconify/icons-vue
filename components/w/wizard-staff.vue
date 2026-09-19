<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd1w9bcas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qd1w9bcas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wizard-staff" /></template>
