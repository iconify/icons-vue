<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tltgrpfit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tltgrpfit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panels-right-bottom-sharp-fill" /></template>
