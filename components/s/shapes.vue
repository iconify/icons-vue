<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh4teh6rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh4teh6rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shapes" /></template>
