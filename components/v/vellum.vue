<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm9k5wb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":174,"height":53};
const content = `<path class="qm9k5wb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vellum" /></template>
