<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgyzkzbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tgyzkzbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:waning-cresent-moon-remix" /></template>
