<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhzr79rbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhzr79rbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:plus" /></template>
