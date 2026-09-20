<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u424brbrp.css';
import '../../css/b/bdi3fdcsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u424brbrp"/><path class="bdi3fdcsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:workflow-teamwork-user-high-five-bold" /></template>
