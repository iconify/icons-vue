<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6i-76zpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m6i-76zpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:superuser" /></template>
