<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx4pedbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fx4pedbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:vm-compact" /></template>
