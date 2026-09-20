<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gepc7-94s.css';
import '../../css/u/ud-710byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gepc7-94s"/><path class="ud-710byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:microsoft-teams" /></template>
