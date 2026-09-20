<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_e1c9-on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_e1c9-on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:painting-fill" /></template>
