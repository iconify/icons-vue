<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq2todbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iq2todbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:postgresql-light" /></template>
