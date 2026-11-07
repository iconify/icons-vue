<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrxlgg64z.css';
import '../../css/g/g5ezogbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="g5ezogbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:restart-circle-bold-duotone" /></template>
