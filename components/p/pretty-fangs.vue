<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j72iiybcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j72iiybcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pretty-fangs" /></template>
