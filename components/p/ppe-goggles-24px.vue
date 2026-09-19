<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alc589sng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="alc589sng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-goggles-24px" /></template>
