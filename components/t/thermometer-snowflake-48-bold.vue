<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz-knsbvd.css';
import '../../css/u/umxpd67pc.css';
import '../../css/u/usgxssb2k.css';
import '../../css/r/rnrvi0mga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vz-knsbvd"/><path class="umxpd67pc"/><path class="usgxssb2k"/><path class="rnrvi0mga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-snowflake-48-bold" /></template>
