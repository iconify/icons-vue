<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppcczsdck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppcczsdck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:voicemail-gloss" /></template>
