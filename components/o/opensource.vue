<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkerobcrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":991};
const content = `<path class="jkerobcrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:opensource" /></template>
