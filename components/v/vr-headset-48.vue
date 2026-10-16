<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj4_8bb8s.css';
import '../../css/a/a5tfz-sap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uj4_8bb8s"/><path class="a5tfz-sap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vr-headset-48" /></template>
