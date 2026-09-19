<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em2d4achx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em2d4achx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:right-arrow-alt" /></template>
