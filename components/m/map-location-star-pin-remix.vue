<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs9cfibno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bs9cfibno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:map-location-star-pin-remix" /></template>
