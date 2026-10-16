<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef0-97kcs.css';
import '../../css/p/plk_--7pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ef0-97kcs"/><path class="plk_--7pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plug-uk-48-bold" /></template>
