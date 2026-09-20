<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2x231juw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2x231juw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:more" /></template>
