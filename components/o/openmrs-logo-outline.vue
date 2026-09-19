<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmd40gk4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bmd40gk4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:openmrs-logo-outline" /></template>
