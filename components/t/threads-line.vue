<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8asrggrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8asrggrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:threads-line" /></template>
