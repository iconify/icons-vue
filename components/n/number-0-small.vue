<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz1z3f7on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz1z3f7on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-0-small" /></template>
