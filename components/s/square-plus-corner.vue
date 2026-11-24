<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0fjt0b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0fjt0b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:square-plus-corner" /></template>
