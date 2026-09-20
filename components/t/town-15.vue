<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_o8_ue3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e_o8_ue3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:town-15" /></template>
