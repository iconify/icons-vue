<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gth9q0crr.css';
import '../../css/i/ia3sgrbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gth9q0crr"/><path class="ia3sgrbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:storage-hdd-2" /></template>
