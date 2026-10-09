<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8al9ob1t.css';
import '../../css/u/us-05tkac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n8al9ob1t"/><path class="us-05tkac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ruler-48-bold" /></template>
