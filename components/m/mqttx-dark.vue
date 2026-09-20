<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6ae_qf3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r6ae_qf3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mqttx-dark" /></template>
