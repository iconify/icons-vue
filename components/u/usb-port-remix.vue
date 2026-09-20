<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orc8ezjzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="orc8ezjzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:usb-port-remix" /></template>
