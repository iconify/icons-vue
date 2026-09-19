<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omq0cw--l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="omq0cw--l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:master-of-arms" /></template>
