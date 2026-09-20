<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-4bf8boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-4bf8boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:pen-draw" /></template>
