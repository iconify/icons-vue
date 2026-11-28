<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klx41e55r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klx41e55r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:syringe-clock" /></template>
