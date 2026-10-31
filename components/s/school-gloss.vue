<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x00daac_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x00daac_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:school-gloss" /></template>
