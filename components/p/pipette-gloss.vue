<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypvqe6-il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k ypvqe6-il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pipette-gloss" /></template>
