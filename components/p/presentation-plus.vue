<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elkic2khp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elkic2khp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:presentation-plus" /></template>
