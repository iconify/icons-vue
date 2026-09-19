<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9osicbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s9osicbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:thermometer-one" /></template>
