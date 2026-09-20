<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4cgdcmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bp4cgdcmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:opera" /></template>
