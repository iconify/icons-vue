<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r605gn10z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1792};
const content = `<path class="r605gn10z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:modx" /></template>
