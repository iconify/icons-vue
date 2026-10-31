<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdqj9mbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdqj9mbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:picture-in-picture-round" /></template>
