<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei8g-eb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei8g-eb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:open-access" /></template>
