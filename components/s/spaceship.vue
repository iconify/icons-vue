<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpgbuk-9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpgbuk-9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spaceship" /></template>
