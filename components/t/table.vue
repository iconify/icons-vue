<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghy4bbcrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghy4bbcrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:table" /></template>
