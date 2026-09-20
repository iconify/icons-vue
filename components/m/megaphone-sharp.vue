<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jof85mv9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jof85mv9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:megaphone-sharp" /></template>
