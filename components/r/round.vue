<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9v4wgnrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="h9v4wgnrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:round" /></template>
