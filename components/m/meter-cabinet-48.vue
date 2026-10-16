<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neu7wrbqd.css';
import '../../css/c/cero_9xdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="neu7wrbqd"/><path class="cero_9xdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:meter-cabinet-48" /></template>
