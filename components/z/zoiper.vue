<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbbc0ebce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbbc0ebce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zoiper" /></template>
