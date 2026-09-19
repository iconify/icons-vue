<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knxuh1edf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knxuh1edf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:valetudo" /></template>
