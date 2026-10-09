<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9uvctq-c.css';
import '../../css/p/ps4u58b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d9uvctq-c"/><path class="ps4u58b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:street-light-48" /></template>
