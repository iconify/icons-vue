<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptf8xy91h.css';
import '../../css/m/m5ugsmtmc.css';
import '../../css/x/xwycoosoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ptf8xy91h"/><path class="m5ugsmtmc"/><circle class="xwycoosoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:pawn" /></template>
