<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9j6_rzjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9j6_rzjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stop-gloss" /></template>
