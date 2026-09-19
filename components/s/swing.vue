<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lub9q8fhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lub9q8fhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:swing" /></template>
