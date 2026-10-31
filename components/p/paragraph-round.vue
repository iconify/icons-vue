<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjvooib1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjvooib1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paragraph-round" /></template>
