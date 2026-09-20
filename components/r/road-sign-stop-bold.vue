<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcutg2b4x.css';
import '../../css/m/m5w08nblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcutg2b4x"/><path class="m5w08nblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:road-sign-stop-bold" /></template>
