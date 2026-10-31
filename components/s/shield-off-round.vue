<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2vctekuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2vctekuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-round" /></template>
