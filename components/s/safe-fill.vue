<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prqia3bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prqia3bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:safe-fill" /></template>
