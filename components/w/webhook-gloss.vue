<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7_amzb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7_amzb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:webhook-gloss" /></template>
