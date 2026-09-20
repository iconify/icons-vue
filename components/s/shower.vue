<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdu0okbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gdu0okbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:shower" /></template>
