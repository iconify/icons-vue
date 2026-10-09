<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm2wf78uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gm2wf78uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sparkles-20-bold" /></template>
