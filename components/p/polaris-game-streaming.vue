<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz881ov0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dz881ov0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:polaris-game-streaming" /></template>
