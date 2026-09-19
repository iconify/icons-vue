<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uipcn5jcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uipcn5jcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:read" /></template>
