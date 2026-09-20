<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ili7pu_wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ili7pu_wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wp-rocket" /></template>
