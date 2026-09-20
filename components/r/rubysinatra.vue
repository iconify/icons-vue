<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnw475f6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnw475f6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rubysinatra" /></template>
