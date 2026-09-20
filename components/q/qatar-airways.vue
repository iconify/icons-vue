<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcl7avbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcl7avbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qatar-airways" /></template>
