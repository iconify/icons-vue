<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge83h09-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge83h09-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:wear-goggles" /></template>
