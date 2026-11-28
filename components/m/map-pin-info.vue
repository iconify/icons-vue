<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs0fk7e4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs0fk7e4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-pin-info" /></template>
