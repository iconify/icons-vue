<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sysz87b-k.css';
import '../../css/k/k5mfz-beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sysz87b-k"/><path class="k5mfz-beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:workflow-48-bold" /></template>
