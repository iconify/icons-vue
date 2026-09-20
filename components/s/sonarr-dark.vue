<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfrv3tbut.css';
import '../../css/v/vzh-lybal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mfrv3tbut"/><path class="vzh-lybal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonarr-dark" /></template>
