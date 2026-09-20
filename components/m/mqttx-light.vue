<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dio2vj7yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dio2vj7yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mqttx-light" /></template>
