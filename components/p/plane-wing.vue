<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo5ta_uie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wo5ta_uie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plane-wing" /></template>
