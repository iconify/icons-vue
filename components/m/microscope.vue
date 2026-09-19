<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ernsnbc0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ernsnbc0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:microscope" /></template>
