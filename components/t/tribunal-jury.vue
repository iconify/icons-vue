<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nby1hwv0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nby1hwv0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tribunal-jury" /></template>
