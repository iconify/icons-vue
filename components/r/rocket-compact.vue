<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-5919gss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b-5919gss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:rocket-compact" /></template>
