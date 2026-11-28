<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frv3y-b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frv3y-b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:router-lock" /></template>
