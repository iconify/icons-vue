<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5aelq3-p.css';
import '../../css/r/r6ik5x-ce.css';
import '../../css/m/mp3pi0u8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5aelq3-p"/><path class="r6ik5x-ce"/><path class="mp3pi0u8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:saltcorn" /></template>
