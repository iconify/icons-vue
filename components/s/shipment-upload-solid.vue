<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il9zs3bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="il9zs3bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:shipment-upload-solid" /></template>
