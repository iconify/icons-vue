<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh-zu0p9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fh-zu0p9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sunset" /></template>
