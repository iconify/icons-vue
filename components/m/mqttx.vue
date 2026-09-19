<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9yr7ib5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9yr7ib5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mqttx" /></template>
