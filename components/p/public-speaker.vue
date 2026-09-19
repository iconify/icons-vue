<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byx7xvb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="byx7xvb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:public-speaker" /></template>
