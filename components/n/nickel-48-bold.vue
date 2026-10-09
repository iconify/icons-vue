<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omdaj5bmv.css';
import '../../css/a/aq7muybgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="omdaj5bmv"/><path class="aq7muybgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nickel-48-bold" /></template>
