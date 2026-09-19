<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds166cc_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ds166cc_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:open-folder" /></template>
