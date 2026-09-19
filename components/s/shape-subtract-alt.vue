<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slu5h6ecs.css';
import '../../css/f/fu5ar-14p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slu5h6ecs"/><path class="fu5ar-14p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-subtract-alt" /></template>
