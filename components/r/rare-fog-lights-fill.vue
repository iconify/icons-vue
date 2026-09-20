<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q55a64brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q55a64brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rare-fog-lights-fill" /></template>
