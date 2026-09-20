<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anom_cxjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="anom_cxjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:synchronize-solid" /></template>
