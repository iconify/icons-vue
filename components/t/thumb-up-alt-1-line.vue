<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9webgb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9webgb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:thumb-up-alt-1-line" /></template>
