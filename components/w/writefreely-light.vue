<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwapn2_9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwapn2_9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:writefreely-light" /></template>
