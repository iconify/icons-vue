<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmufk39sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmufk39sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-receipt-alert" /></template>
