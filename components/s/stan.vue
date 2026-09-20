<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfq33mb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="dfq33mb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:stan" /></template>
