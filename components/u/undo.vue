<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbgp3bhag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbgp3bhag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:undo" /></template>
