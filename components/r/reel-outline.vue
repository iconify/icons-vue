<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyzuu4cmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyzuu4cmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reel-outline" /></template>
