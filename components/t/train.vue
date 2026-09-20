<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjw6eqb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="fjw6eqb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:train" /></template>
