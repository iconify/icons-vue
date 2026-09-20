<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcebbxirw.css';
import '../../css/m/m374-eb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tcebbxirw"/><path class="m374-eb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:paypal-original" /></template>
