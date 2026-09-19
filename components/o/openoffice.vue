<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su8pud0wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="su8pud0wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:openoffice" /></template>
