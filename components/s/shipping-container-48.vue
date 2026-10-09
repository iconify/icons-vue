<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay__5bcmu.css';
import '../../css/f/ff8py9bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ay__5bcmu"/><path class="ff8py9bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shipping-container-48" /></template>
