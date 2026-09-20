<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mng4_v46u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mng4_v46u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-3d-nozzle" /></template>
