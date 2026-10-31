<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn44f8b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn44f8b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-alt-1-round" /></template>
