<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_0vfbc6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_0vfbc6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:netflix" /></template>
