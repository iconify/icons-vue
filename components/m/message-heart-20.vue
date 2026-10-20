<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzs5177np.css';
import '../../css/j/jmz-_09oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fzs5177np"/><path class="jmz-_09oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-heart-20" /></template>
