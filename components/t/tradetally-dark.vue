<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgttro11x.css';
import '../../css/d/dl8utqb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgttro11x"/><path class="dl8utqb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tradetally-dark" /></template>
