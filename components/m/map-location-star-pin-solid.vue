<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2eswrgdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o2eswrgdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:map-location-star-pin-solid" /></template>
