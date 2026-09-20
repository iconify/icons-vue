<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukyfr_b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ukyfr_b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signage-3-remix" /></template>
