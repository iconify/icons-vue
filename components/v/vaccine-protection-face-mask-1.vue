<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y16uqnbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y16uqnbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:vaccine-protection-face-mask-1" /></template>
