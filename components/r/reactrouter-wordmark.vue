<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v40o2_bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v40o2_bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:reactrouter-wordmark" /></template>
