<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w31fx27ee.css';
import '../../css/i/iorf4rbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w31fx27ee"/><path class="iorf4rbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pellet-boiler-48-bold" /></template>
