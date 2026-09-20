<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ych5b6ltu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ych5b6ltu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openai-gym" /></template>
