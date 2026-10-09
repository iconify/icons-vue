<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqhdcmbrc.css';
import '../../css/a/aemqdzbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oqhdcmbrc"/><path class="aemqdzbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-pin-off-20-bold" /></template>
