<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boycur6dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boycur6dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:muo" /></template>
