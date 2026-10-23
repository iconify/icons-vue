<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciph4tade.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciph4tade"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:map-pin-pen" /></template>
