<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f72o4bbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f72o4bbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:spinner-alt" /></template>
