<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgfp4e6dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgfp4e6dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pln" /></template>
