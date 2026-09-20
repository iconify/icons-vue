<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df-d0zb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="df-d0zb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:threat-phone-remix" /></template>
