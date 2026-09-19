<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvz-8k5oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gvz-8k5oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ring" /></template>
