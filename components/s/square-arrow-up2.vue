<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-umg8bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-umg8bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-up2" /></template>
