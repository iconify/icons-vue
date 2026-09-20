<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf6irmbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf6irmbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:robot-3-line" /></template>
