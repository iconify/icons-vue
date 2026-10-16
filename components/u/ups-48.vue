<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-flw2bql.css';
import '../../css/i/ihgrfnbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m-flw2bql"/><path class="ihgrfnbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ups-48" /></template>
