<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldjtx9lab.css';
import '../../css/m/mrqn0ob3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldjtx9lab"/><path class="mrqn0ob3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:more-4-line" /></template>
