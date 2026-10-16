<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snsrwjb2q.css';
import '../../css/a/a35pl3byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="snsrwjb2q"/><path class="a35pl3byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermistor-48" /></template>
