<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jngd8gbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jngd8gbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:spdx" /></template>
