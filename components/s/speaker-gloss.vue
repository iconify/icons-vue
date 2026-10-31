<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coos0r0bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coos0r0bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:speaker-gloss" /></template>
