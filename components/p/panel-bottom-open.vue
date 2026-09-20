<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogzdbruwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogzdbruwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-open" /></template>
