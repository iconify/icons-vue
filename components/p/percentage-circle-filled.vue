<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4cbddb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4cbddb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:percentage-circle-filled" /></template>
