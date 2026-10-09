<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vghbbfb2f.css';
import '../../css/p/pw56fm25u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vghbbfb2f"/><path class="pw56fm25u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pellet-boiler-48" /></template>
