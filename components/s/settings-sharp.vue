<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojz440bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojz440bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:settings-sharp" /></template>
