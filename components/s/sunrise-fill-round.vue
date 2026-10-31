<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m79vz3mgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m79vz3mgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sunrise-fill-round" /></template>
