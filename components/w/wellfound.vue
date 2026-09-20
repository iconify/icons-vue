<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfms_lx4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfms_lx4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wellfound" /></template>
