<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyl30e_uw.css';
import '../../css/v/vg4zk5bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fyl30e_uw"/><path class="vg4zk5bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:share-48" /></template>
