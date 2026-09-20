<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muwff1hjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="muwff1hjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-round-outline" /></template>
