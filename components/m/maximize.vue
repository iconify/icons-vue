<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfuiahb8m.css';
import '../../css/d/dnd7e2h4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tfuiahb8m"/><path class="dnd7e2h4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:maximize" /></template>
