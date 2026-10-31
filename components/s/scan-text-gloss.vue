<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xotu9nmgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xotu9nmgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-text-gloss" /></template>
