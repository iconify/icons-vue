<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh2xf-bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mh2xf-bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-rounded-triangle-down" /></template>
