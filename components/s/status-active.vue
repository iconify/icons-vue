<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obl5gdplp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="obl5gdplp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:status-active" /></template>
