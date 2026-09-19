<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5surlbgg.css';
import '../../css/s/stpx8h04v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c5surlbgg"/><path class="stpx8h04v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:open-sharp" /></template>
