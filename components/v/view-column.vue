<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr_sywbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lr_sywbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:view-column" /></template>
