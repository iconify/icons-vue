<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bosmi-hbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bosmi-hbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-low-48" /></template>
