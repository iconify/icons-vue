<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs1lw6mbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gs1lw6mbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-question-sharp-fill" /></template>
