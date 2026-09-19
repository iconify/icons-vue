<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-mm2yblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a-mm2yblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:viola" /></template>
