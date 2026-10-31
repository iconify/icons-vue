<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m81vs0cnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m81vs0cnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-full-fill-round" /></template>
