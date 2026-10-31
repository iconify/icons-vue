<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7e6b-das.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7e6b-das"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-round" /></template>
