<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2hyr4bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b2hyr4bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tapir" /></template>
