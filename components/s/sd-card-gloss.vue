<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwntrmbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwntrmbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sd-card-gloss" /></template>
