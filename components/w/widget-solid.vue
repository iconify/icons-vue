<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuijogbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="iuijogbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:widget-solid" /></template>
