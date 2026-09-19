<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdmx7eosl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wdmx7eosl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:rectangle-one" /></template>
