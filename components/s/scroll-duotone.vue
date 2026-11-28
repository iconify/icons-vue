<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bajsucc6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bajsucc6j primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scroll-duotone" /></template>
