<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9em7nbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9em7nbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:path" /></template>
