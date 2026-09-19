<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5dbdpbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t5dbdpbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:philosopher-bust" /></template>
