<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/estb-abdk.css';
import '../../css/d/dicdvz1vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="estb-abdk"/><path class="dicdvz1vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:qa-4x3" /></template>
