<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz30cqbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jz30cqbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:woozy-face-in-circle" /></template>
