<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awo_d-8ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="awo_d-8ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-forms-2016-light" /></template>
