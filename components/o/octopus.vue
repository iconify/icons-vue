<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jab0fccmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jab0fccmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:octopus" /></template>
