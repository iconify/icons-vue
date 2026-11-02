<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc21p692x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc21p692x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-2-fill" /></template>
