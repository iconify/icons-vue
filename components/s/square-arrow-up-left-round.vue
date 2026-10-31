<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkgzhfbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkgzhfbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-up-left-round" /></template>
