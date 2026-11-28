<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd5z3d9fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd5z3d9fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message-square-plus" /></template>
