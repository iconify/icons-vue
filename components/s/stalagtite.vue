<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb9h83bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vb9h83bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stalagtite" /></template>
